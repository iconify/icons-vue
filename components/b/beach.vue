<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfjjnwb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cfjjnwb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:beach" /></template>
