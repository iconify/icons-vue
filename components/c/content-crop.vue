<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4-dr1gfb.css';
import '../../css/q/qql1b-83c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x4-dr1gfb"/><path class="qql1b-83c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-crop" /></template>
