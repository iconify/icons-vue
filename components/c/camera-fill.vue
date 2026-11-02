<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4m3z1bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4m3z1bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-fill" /></template>
