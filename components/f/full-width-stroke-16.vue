<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2m0k31jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s2m0k31jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:full-width-stroke-16" /></template>
