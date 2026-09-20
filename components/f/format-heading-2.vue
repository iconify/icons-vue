<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx3slkn2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx3slkn2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-2" /></template>
