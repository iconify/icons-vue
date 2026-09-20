<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-8blkbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i-8blkbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-down-right" /></template>
