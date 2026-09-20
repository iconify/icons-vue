<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da0ws9bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da0ws9bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-item-vertical-center-line" /></template>
