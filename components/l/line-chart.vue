<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qac519had.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qac519had"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:line-chart" /></template>
