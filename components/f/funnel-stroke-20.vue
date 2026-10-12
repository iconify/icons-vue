<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igjciebul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="igjciebul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:funnel-stroke-20" /></template>
