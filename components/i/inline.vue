<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyu-dyi9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyu-dyi9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:inline" /></template>
