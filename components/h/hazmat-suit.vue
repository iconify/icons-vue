<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_p5mfb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y_p5mfb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hazmat-suit" /></template>
