<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj6pdebvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qj6pdebvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-movie-outline" /></template>
