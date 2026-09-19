<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjfgxxodz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qjfgxxodz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:godot-assets" /></template>
