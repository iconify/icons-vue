<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haqr67bmp.css';
import '../../css/e/e2-vdac3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haqr67bmp"/><path class="e2-vdac3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-front-line" /></template>
