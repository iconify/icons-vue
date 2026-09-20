<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_0a0bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ae_0a0bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-right" /></template>
