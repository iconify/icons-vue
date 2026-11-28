<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2-3w5b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2-3w5b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contract-search" /></template>
