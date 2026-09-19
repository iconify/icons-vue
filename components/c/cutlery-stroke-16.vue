<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj-99yt8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xj-99yt8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cutlery-stroke-16" /></template>
