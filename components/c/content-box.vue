<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1dx6ebyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1dx6ebyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-box" /></template>
