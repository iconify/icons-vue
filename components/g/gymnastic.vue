<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a0tu6zjre.css';
import '../../css/d/d3p2npepl.css';
import '../../css/u/uahprbbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0tu6zjre"/><path class="d3p2npepl"/><path class="uahprbbwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gymnastic" /></template>
