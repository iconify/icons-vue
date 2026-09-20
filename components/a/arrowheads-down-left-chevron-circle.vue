<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-xz9t4wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-xz9t4wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-down-left-chevron-circle" /></template>
