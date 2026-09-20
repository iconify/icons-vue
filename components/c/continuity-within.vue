<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv_9n7-1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xv_9n7-1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:continuity-within" /></template>
