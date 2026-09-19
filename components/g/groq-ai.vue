<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfwi9t47h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfwi9t47h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:groq-ai" /></template>
