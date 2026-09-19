<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no7qesbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="no7qesbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:json" /></template>
