<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwdlzlcce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nwdlzlcce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chart-bar-16-solid" /></template>
