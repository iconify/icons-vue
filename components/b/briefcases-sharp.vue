<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4u0-9bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4u0-9bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:briefcases-sharp" /></template>
