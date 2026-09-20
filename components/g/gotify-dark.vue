<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ees4jqgyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="ees4jqgyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gotify-dark" /></template>
