<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktdhq7xuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktdhq7xuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cog-play-outline" /></template>
