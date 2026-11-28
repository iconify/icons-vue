<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxx0n92ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uxx0n92ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-clock-thin" /></template>
