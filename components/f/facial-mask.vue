<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nde60ab7m.css';
import '../../css/e/ez_zj8b4g.css';
import '../../css/a/arg04jbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nde60ab7m"/><path class="ez_zj8b4g"/><path class="arg04jbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:facial-mask" /></template>
