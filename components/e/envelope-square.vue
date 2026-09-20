<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8o8gmbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u8o8gmbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:envelope-square" /></template>
