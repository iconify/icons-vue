<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh3jj2bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yh3jj2bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-right-chevron-circle" /></template>
