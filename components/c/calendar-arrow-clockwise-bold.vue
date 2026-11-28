<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn4o5mb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cn4o5mb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-clockwise-bold" /></template>
