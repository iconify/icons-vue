<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/px6wupeym.css';
import '../../css/o/opvumqbnq.css';
import '../../css/d/dr9gut14h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="px6wupeym"/><path class="opvumqbnq"/><path class="dr9gut14h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bean" /></template>
