<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-k1sjv1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e-k1sjv1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-clockwise-light" /></template>
