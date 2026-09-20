<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifjip30_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ifjip30_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:calendar" /></template>
