<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thowymt8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="thowymt8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-out-thin" /></template>
