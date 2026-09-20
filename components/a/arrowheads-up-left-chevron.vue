<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u00wypjwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u00wypjwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-up-left-chevron" /></template>
