<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi__8e8vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="fi__8e8vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:close" /></template>
