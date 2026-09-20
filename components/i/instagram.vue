<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dfrhk1b-s.css';
import '../../css/a/a58ac9brq.css';
import '../../css/c/c8x8g5sqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="dfrhk1b-s"/><path class="a58ac9brq"/><circle class="c8x8g5sqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:instagram" /></template>
