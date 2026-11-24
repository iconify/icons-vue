<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj1o8w1sa.css';
import '../../css/h/hihrgrzxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1o8w1sa"/><path class="hihrgrzxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-rain-filled" /></template>
