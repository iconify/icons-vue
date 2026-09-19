<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4zscvu3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4zscvu3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:loft-3d" /></template>
