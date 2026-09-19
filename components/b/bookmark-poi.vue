<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie9k28r9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ie9k28r9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:bookmark-poi" /></template>
