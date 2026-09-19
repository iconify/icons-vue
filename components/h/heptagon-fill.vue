<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3f49ybrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3f49ybrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:heptagon-fill" /></template>
