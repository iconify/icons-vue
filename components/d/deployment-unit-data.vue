<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs5lclkzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cs5lclkzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deployment-unit-data" /></template>
