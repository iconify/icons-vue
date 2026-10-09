<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h82f8zb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h82f8zb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hexagon-20" /></template>
