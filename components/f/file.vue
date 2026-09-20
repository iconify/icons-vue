<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-kvv8b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-kvv8b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:file" /></template>
