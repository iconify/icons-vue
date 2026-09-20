<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz__0t3bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz__0t3bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-text-sharp" /></template>
