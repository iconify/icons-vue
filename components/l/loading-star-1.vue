<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7-w0bcuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-w0bcuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:loading-star-1" /></template>
