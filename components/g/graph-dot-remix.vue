<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5sex-bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p5sex-bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:graph-dot-remix" /></template>
