<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga4y_tbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga4y_tbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-heart-fill" /></template>
