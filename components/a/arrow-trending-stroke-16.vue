<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwmdiebxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lwmdiebxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-trending-stroke-16" /></template>
