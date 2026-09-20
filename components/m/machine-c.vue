<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycq1qfcwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ycq1qfcwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:machine-c" /></template>
