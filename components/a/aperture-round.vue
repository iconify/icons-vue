<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feu6ydgps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feu6ydgps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aperture-round" /></template>
