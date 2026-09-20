<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy0mtp5eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fy0mtp5eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hunting-blind" /></template>
