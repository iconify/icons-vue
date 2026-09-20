<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1p332b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1p332b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-q-circle-outline" /></template>
