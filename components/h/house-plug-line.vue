<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi8bvlbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi8bvlbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-plug-line" /></template>
