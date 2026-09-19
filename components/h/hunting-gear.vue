<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zt58lacpe.css';
import '../../css/m/mzhpw8m7u.css';
import '../../css/r/ru8717ryg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="zt58lacpe"/><path class="mzhpw8m7u"/><path class="ru8717ryg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hunting-gear" /></template>
