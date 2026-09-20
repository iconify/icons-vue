<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm-lq5bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dm-lq5bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:grid-vertical" /></template>
