<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fce5mu9wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fce5mu9wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:link-outline" /></template>
