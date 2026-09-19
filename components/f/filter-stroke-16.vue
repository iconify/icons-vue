<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssah3cbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ssah3cbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:filter-stroke-16" /></template>
