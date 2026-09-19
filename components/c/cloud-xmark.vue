<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu4-uvb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu4-uvb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cloud-xmark" /></template>
