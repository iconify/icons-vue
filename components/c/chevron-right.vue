<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvbcs1z_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rvbcs1z_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:chevron-right" /></template>
