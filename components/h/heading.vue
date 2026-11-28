<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv2me7lcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv2me7lcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heading" /></template>
