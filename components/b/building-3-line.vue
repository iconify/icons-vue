<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr60ftpbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr60ftpbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:building-3-line" /></template>
