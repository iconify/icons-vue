<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr5jq2bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr5jq2bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-justify-end-line" /></template>
