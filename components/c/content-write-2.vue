<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9eu5vbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d9eu5vbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-write-2" /></template>
