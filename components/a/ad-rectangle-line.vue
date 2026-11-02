<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-pjm-3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy-pjm-3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-rectangle-line" /></template>
