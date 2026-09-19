<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dekr_0bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dekr_0bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gatsby" /></template>
