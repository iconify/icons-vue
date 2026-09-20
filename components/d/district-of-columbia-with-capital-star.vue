<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9dr1ubsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e9dr1ubsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:district-of-columbia-with-capital-star" /></template>
