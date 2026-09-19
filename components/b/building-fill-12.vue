<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awuo_7k1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="awuo_7k1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:building-fill-12" /></template>
