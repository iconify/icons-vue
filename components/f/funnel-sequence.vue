<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb77bixnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb77bixnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:funnel-sequence" /></template>
