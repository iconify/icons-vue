<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzl2nbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="czzl2nbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-horizontal-16" /></template>
