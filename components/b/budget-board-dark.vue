<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3vxdac3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e3vxdac3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budget-board-dark" /></template>
