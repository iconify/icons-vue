<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgx4fhnss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="xgx4fhnss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:krw" /></template>
