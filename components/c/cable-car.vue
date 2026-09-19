<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0c2d3bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0c2d3bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cable-car" /></template>
