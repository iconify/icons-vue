<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agxl_l40w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agxl_l40w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-share-3" /></template>
