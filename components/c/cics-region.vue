<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8hewfc3o.css';
import '../../css/b/b_p-ebbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w8hewfc3o"/><path class="b_p-ebbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-region" /></template>
