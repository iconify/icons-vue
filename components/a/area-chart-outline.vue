<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veb76gruq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="veb76gruq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:area-chart-outline" /></template>
