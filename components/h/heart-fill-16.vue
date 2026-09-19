<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3j1vl57g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p3j1vl57g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heart-fill-16" /></template>
