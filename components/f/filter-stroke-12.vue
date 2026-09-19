<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc5qq84az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yc5qq84az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:filter-stroke-12" /></template>
