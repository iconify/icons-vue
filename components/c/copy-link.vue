<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0_aafh7s.css';
import '../../css/o/oasg37s7n.css';
import '../../css/k/kfsga1-1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h0_aafh7s"/><path class="oasg37s7n"/><path class="kfsga1-1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:copy-link" /></template>
