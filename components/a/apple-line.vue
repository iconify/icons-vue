<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbiftsbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbiftsbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:apple-line" /></template>
