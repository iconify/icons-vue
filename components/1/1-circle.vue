<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp_tly-yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vp_tly-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:1-circle" /></template>
