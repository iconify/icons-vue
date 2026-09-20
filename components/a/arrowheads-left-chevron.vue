<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahhxt3bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ahhxt3bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-left-chevron" /></template>
