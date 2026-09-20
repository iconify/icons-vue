<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3fl0b47k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3fl0b47k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:lasso-tool-remix" /></template>
