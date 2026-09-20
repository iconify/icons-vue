<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km-r1bbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km-r1bbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:circle-question" /></template>
