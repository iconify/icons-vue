<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb0oq1bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nb0oq1bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:drag-dots" /></template>
