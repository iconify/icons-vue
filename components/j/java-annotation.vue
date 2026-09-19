<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zijtqfbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zijtqfbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:java-annotation" /></template>
