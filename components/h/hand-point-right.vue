<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8g6hdbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8g6hdbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-point-right" /></template>
