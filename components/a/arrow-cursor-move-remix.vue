<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5n1a1dep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p5n1a1dep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-cursor-move-remix" /></template>
