<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39acgbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r39acgbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:grid-view-medium" /></template>
