<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn_x731ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zn_x731ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:at-stroke-12" /></template>
