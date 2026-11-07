<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xydt5snoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xydt5snoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-linear" /></template>
