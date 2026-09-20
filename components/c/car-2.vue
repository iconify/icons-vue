<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u29ffvbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u29ffvbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:car-2" /></template>
