<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d35pi9b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d35pi9b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cloak" /></template>
