<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtbhzfbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dtbhzfbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bottles-01" /></template>
