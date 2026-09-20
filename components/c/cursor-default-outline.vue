<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb0fx9bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb0fx9bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-default-outline" /></template>
