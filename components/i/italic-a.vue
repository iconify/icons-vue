<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/funjsb_-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="funjsb_-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-a" /></template>
