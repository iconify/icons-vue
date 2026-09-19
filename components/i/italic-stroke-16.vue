<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6ngt0_3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6ngt0_3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:italic-stroke-16" /></template>
