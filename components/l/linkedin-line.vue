<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy9vcx_4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy9vcx_4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:linkedin-line" /></template>
