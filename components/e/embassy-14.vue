<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv2_7ilyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cv2_7ilyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:embassy-14" /></template>
