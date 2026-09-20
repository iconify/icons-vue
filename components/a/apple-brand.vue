<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb4yoebdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb4yoebdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:apple-brand" /></template>
