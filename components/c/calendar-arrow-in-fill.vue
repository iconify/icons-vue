<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8giv7biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p8giv7biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-in-fill" /></template>
