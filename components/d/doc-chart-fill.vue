<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrp5dfmsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xrp5dfmsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-chart-fill" /></template>
