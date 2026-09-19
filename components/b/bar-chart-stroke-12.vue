<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckpvr9csx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ckpvr9csx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-stroke-12" /></template>
