<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlmscut1c.css';
import '../../css/s/sx9ljtq-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jlmscut1c"/><path class="sx9ljtq-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:audio" /></template>
