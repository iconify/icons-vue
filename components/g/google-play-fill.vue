<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6yv8ac1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yv8ac1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:google-play-fill" /></template>
