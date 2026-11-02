<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpw3vkzya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpw3vkzya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rupee-fill" /></template>
