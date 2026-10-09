<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0n2bubor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d0n2bubor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:infinity-20-bold" /></template>
