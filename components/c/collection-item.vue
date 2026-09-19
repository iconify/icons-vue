<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faql0lbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="faql0lbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-item" /></template>
