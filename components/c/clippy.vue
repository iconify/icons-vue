<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwmrae3sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwmrae3sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clippy" /></template>
