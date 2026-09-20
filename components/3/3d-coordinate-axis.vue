<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nomj558xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nomj558xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:3d-coordinate-axis" /></template>
