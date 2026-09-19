<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3ugng94a.css';
import '../../css/f/f-_fxyb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w3ugng94a"/><path class="f-_fxyb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-windows" /></template>
