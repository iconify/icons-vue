<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn0-u2b-e.css';
import '../../css/i/i4_lnxbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn0-u2b-e"/><path class="i4_lnxbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-column-target" /></template>
