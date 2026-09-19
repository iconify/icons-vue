<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q90_u7bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="q90_u7bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:copy-poly" /></template>
