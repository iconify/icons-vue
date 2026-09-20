<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov0lzdbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ov0lzdbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badge-shield-with-exclamation-point" /></template>
