<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_0zv4bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_0zv4bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gl-inet-light" /></template>
