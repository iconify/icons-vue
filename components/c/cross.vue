<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrk3srbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrk3srbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cross" /></template>
