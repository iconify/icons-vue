<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml2bg2b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ml2bg2b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-right-circle" /></template>
