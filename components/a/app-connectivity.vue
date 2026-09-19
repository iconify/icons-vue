<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4_w-d8ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f4_w-d8ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:app-connectivity" /></template>
