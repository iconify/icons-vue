<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvs79mmwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kvs79mmwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:calendar" /></template>
