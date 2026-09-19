<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0lx5-bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0lx5-bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-pause" /></template>
