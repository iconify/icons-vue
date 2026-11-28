<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2_qtmcnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2_qtmcnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevron-down" /></template>
