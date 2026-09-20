<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpu-0cats.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wpu-0cats"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bar-chart-outline" /></template>
