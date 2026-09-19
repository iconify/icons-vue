<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhse-g5zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fhse-g5zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-center-stroke-16" /></template>
