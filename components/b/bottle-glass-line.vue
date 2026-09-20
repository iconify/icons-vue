<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy-i9xb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy-i9xb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bottle-glass-line" /></template>
