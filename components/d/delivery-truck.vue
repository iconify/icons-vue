<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf7wg8b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bf7wg8b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delivery-truck" /></template>
