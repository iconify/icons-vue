<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inif3yb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="inif3yb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise-16-solid" /></template>
