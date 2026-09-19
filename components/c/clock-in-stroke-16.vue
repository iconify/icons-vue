<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ust54ibwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ust54ibwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-in-stroke-16" /></template>
