<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6f-icc4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q6f-icc4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:easel" /></template>
