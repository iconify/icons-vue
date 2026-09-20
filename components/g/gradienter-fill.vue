<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f__kf5b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f__kf5b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gradienter-fill" /></template>
