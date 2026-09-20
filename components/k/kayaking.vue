<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugu5vab6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugu5vab6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kayaking" /></template>
