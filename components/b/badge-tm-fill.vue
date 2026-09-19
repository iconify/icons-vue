<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpxaggc5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gpxaggc5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:badge-tm-fill" /></template>
