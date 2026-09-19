<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vrc15wbok.css';
import '../../css/d/dw6mr4b-d.css';
import '../../css/o/ov04m3g9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vrc15wbok"/><path class="dw6mr4b-d"/><path class="ov04m3g9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:garage-duo" /></template>
