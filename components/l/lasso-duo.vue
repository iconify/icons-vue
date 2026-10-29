<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ll_-f9b-g.css';
import '../../css/g/gxjs16b5s.css';
import '../../css/k/k56gh1yvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ll_-f9b-g wm-a"/><path class="gxjs16b5s wm-a"/><path class="k56gh1yvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lasso-duo" /></template>
