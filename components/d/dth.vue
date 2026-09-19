<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w85oa8b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w85oa8b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dth" /></template>
