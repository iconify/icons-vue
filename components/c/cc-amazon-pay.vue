<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0ysjab1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u0ysjab1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-amazon-pay" /></template>
