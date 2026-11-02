<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us95y-boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us95y-boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-heart-line" /></template>
