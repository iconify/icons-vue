<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er7ajtbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="er7ajtbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:business-progress-bar-2" /></template>
