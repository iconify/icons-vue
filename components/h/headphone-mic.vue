<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drzam248w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drzam248w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:headphone-mic" /></template>
