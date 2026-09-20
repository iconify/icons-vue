<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3uhupbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3uhupbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chart-pie-solid" /></template>
