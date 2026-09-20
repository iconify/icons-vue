<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz9d3bbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9d3bbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-distribute-start-sharp" /></template>
