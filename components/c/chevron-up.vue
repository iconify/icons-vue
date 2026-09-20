<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wewv2-b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wewv2-b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:chevron-up" /></template>
