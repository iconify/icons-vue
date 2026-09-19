<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyp086bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uyp086bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-line-stroke-16" /></template>
