<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3wdlk2ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d3wdlk2ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-round-left-flat" /></template>
