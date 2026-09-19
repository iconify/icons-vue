<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux3o_f6vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ux3o_f6vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:drawio" /></template>
