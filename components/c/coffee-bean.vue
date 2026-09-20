<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq1py1b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cq1py1b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffee-bean" /></template>
