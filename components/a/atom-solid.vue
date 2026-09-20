<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa6bx_bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fa6bx_bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:atom-solid" /></template>
