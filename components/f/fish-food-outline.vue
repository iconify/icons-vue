<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g42g6mlbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g42g6mlbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fish-food-outline" /></template>
