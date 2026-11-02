<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_raj1b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_raj1b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-line" /></template>
