<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxtlldbyo.css';
import '../../css/d/dezgnhv9l.css';
import '../../css/q/qqf7r7bcl.css';
import '../../css/c/c2ym01bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxtlldbyo"/><path class="dezgnhv9l"/><path class="qqf7r7bcl"/><path class="c2ym01bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dining-table-20" /></template>
