<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fky3noyfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fky3noyfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:butterfly-with-stars-and-dots" /></template>
