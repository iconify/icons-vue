<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0xr4npzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d0xr4npzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bacteria" /></template>
