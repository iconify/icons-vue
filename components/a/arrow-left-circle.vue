<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6eiweb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6eiweb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-left-circle" /></template>
