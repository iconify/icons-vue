<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac8ulaccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac8ulaccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chart-column-decreasing-sharp" /></template>
