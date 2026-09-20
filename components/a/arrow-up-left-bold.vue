<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvzl4u5ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvzl4u5ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-left-bold" /></template>
