<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj3-q5xdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="rj3-q5xdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:apple" /></template>
