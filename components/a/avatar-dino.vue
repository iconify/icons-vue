<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/z/zw1rcdg2e.css';
import '../../css/b/bsavs7uau.css';
import '../../css/y/y3vgs4o4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="zw1rcdg2e"/><path class="bsavs7uau"/><path class="y3vgs4o4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:avatar-dino" /></template>
