<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccoa8rb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccoa8rb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:horizontal-slider-2-remix" /></template>
