<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfuchnjce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hfuchnjce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-exclamation" /></template>
