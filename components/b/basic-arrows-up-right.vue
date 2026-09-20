<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-gecly6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-gecly6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-up-right" /></template>
