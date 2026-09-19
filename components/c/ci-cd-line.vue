<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4y--i39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u4y--i39e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:ci-cd-line" /></template>
