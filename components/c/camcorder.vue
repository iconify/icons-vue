<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-p2oz0-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i-p2oz0-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:camcorder" /></template>
