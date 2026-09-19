<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewxs8lclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ewxs8lclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deployment-unit-technical-execution" /></template>
