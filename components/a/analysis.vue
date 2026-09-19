<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nw9s1xgqx.css';
import '../../css/z/z-3ptvbim.css';
import '../../css/h/hxw676bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nw9s1xgqx"/><path class="z-3ptvbim"/><path class="hxw676bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:analysis" /></template>
