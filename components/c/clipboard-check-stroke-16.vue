<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovvyb8bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ovvyb8bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-check-stroke-16" /></template>
