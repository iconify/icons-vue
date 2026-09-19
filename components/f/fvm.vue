<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rynp_kb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rynp_kb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:fvm" /></template>
