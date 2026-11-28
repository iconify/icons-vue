<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ream2rr8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ream2rr8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:car-check" /></template>
