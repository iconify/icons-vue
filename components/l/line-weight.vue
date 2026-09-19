<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3a2tccdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3a2tccdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:line-weight" /></template>
