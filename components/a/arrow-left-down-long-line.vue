<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyedc4ayr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyedc4ayr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-down-long-line" /></template>
