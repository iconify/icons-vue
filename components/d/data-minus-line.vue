<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd9vq1gyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd9vq1gyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:data-minus-line" /></template>
