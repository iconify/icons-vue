<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/x5kq9ej_d.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/x/x95g1kbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x5kq9ej_d"/><path class="zr5m9kbwl"/><path class="x95g1kbnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eraser-sparkles-sharp-two-tone" /></template>
