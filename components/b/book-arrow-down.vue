<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvqlh5vpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqlh5vpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-arrow-down" /></template>
