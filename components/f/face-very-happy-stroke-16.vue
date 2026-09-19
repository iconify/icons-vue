<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4xv_n6bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i4xv_n6bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-happy-stroke-16" /></template>
