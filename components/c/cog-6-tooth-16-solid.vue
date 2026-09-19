<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us8x8xi4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="us8x8xi4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cog-6-tooth-16-solid" /></template>
