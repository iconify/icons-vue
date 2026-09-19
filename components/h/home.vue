<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/yl3ib2b4t.css';
import '../../css/d/dj__7_bov.css';
import '../../css/h/h7tnjtbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="yl3ib2b4t"/><path class="dj__7_bov"/><path class="h7tnjtbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:home" /></template>
