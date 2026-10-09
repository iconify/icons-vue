<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyf71qdqm.css';
import '../../css/p/p3488rbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eyf71qdqm"/><path class="p3488rbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-truck-20-bold" /></template>
