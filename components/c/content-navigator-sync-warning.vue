<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flqsn-boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flqsn-boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-navigator-sync-warning" /></template>
