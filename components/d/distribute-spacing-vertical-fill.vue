<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd1hdgbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd1hdgbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:distribute-spacing-vertical-fill" /></template>
