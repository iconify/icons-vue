<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug21vkosq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ug21vkosq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hexagon-strip" /></template>
