<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxth2iboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxth2iboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-relationship" /></template>
