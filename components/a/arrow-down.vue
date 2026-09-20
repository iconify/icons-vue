<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i663cybmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i663cybmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-down" /></template>
