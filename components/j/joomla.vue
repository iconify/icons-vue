<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9fy_5bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9fy_5bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:joomla" /></template>
