<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fal4x0qhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fal4x0qhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-item-bottom-fill" /></template>
