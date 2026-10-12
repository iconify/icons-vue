<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw9vzpbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uw9vzpbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-left-20" /></template>
