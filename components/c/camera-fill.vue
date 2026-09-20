<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc5r50bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc5r50bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-fill" /></template>
