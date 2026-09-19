<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyuiy0bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xyuiy0bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:airplane-engines" /></template>
