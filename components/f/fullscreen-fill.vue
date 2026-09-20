<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0vm8o8_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0vm8o8_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fullscreen-fill" /></template>
