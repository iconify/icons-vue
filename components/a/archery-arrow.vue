<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k292zdxcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k292zdxcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:archery-arrow" /></template>
