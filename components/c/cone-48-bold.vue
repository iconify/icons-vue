<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh3e6tb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zh3e6tb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cone-48-bold" /></template>
