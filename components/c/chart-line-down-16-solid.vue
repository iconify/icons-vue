<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s00qodhty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s00qodhty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chart-line-down-16-solid" /></template>
