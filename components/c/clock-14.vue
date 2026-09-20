<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjymv8b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tjymv8b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:clock-14" /></template>
