<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pnvi2iprk.css';
import '../../css/r/r3if10wmo.css';
import '../../css/s/s8gsd3uwy.css';
import '../../css/g/gaepn6b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pnvi2iprk"/><path clip-rule="evenodd" class="r3if10wmo"/><path class="s8gsd3uwy"/><path clip-rule="evenodd" class="gaepn6b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:child-cognition" /></template>
