<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjbibb21a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qjbibb21a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:fast-forward" /></template>
