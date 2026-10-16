<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4cf0bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zh4cf0bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-mix-48" /></template>
