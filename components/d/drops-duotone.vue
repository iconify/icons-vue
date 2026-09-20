<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r82adyb7b.css';
import '../../css/h/hj8ko8a3r.css';
import '../../css/t/tf1lulb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r82adyb7b"/><path class="hj8ko8a3r"/><path class="tf1lulb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:drops-duotone" /></template>
