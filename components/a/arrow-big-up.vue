<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uidu69k_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uidu69k_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-big-up" /></template>
