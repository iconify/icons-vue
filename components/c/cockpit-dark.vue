<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3fz42bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3fz42bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cockpit-dark" /></template>
