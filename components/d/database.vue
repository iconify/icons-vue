<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csxpon4lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="csxpon4lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:database" /></template>
