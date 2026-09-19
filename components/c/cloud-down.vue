<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mlx2oubwz.css';
import '../../css/v/vok929bes.css';
import '../../css/m/meco3rogb.css';
import '../../css/s/s29ll1g5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mlx2oubwz"/><path class="vok929bes"/><path class="meco3rogb"/><path class="s29ll1g5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:cloud-down" /></template>
