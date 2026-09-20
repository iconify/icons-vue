<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ynw9ue5kw.css';
import '../../css/k/k86_x5j-d.css';
import '../../css/q/qhx2abb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ynw9ue5kw"/><path class="k86_x5j-d"/><path class="qhx2abb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:draw-text" /></template>
