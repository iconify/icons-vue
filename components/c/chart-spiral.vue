<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbh3twb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sbh3twb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-spiral" /></template>
