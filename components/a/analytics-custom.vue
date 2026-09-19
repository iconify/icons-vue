<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dovqwxbmr.css';
import '../../css/m/mvazklbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dovqwxbmr"/><path class="mvazklbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:analytics-custom" /></template>
