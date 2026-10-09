<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1_9j_biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w1_9j_biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-right-48-bold" /></template>
