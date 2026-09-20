<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx-nx6b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qx-nx6b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-on-trailer-on-ramp-on-water" /></template>
