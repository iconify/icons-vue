<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/cnm4tobcu.css';
import '../../css/d/d0kgfogdx.css';
import '../../css/h/hxiqqwbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cnm4tobcu"/><path class="d0kgfogdx"/><path class="hxiqqwbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-off-sharp-two-tone" /></template>
