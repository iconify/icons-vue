<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx4o7-blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx4o7-blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:crop-2-fill" /></template>
