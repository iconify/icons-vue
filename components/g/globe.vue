<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdgnmwbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qdgnmwbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:globe" /></template>
