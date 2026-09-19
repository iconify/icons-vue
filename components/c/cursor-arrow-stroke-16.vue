<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhzkytj8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mhzkytj8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cursor-arrow-stroke-16" /></template>
