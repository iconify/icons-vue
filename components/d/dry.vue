<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq1qi5b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oq1qi5b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:dry" /></template>
