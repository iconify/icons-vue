<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww96v3bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ww96v3bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:clockwise-90-outline" /></template>
