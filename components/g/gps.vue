<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e20m-7bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e20m-7bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gps" /></template>
