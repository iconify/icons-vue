<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxku6lahb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qxku6lahb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-left-16" /></template>
