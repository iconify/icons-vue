<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtmerfb1q.css';
import '../../css/f/fig7n4w6p.css';
import '../../css/u/utvn67bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmerfb1q"/><path class="fig7n4w6p"/><path class="utvn67bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-assets-open" /></template>
