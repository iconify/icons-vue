<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lceo2ybkv.css';
import '../../css/h/hkb4kmbmc.css';
import '../../css/x/xrz9d4b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lceo2ybkv"/><path class="hkb4kmbmc"/><path class="xrz9d4b_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:compass" /></template>
