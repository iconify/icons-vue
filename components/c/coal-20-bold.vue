<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p181rzbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p181rzbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coal-20-bold" /></template>
