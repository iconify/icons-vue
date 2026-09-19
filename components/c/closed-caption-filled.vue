<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6eihob5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z6eihob5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:closed-caption-filled" /></template>
