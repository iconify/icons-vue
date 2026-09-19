<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdaunkhqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdaunkhqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:indent-increase" /></template>
