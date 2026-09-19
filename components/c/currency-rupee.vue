<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ma-1b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x5ma-1b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:currency-rupee" /></template>
