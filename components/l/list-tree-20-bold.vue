<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxj2d1b_f.css';
import '../../css/n/nmhn6wb1y.css';
import '../../css/y/ycfhepb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fxj2d1b_f"/><path class="nmhn6wb1y"/><path class="ycfhepb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-tree-20-bold" /></template>
