<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8oh3cbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g8oh3cbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-left-circle" /></template>
