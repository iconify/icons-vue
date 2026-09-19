<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l62psgbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l62psgbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:left-magnifying-glass-small" /></template>
