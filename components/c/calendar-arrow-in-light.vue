<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh74s0rct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qh74s0rct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-in-light" /></template>
