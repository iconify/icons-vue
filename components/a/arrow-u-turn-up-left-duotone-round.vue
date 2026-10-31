<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc4ggzpns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc4ggzpns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-up-left-duotone-round" /></template>
