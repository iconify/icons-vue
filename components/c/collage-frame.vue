<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_e13acxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_e13acxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:collage-frame" /></template>
