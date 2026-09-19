<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/wnuo3bejw.css';
import '../../css/z/zuxintbbc.css';
import '../../css/u/ux16ifpyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="wnuo3bejw"/><path class="zuxintbbc"/><path class="ux16ifpyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:lamp" /></template>
