<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gimaec7ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gimaec7ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egyptian-pyramids-line" /></template>
