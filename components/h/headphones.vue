<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xesh5zbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xesh5zbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:headphones" /></template>
