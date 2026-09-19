<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d94pbcbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d94pbcbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid-1x2-fill" /></template>
