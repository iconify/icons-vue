<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw3bu8blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jw3bu8blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:forward-10-bold" /></template>
