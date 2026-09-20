<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1bn7-8_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1bn7-8_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:add-grid" /></template>
