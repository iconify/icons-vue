<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aww2hc3xd.css';
import '../../css/d/d3halac9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aww2hc3xd"/><path class="d3halac9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type2-20-bold" /></template>
