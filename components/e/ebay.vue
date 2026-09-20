<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgwa1-1-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgwa1-1-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ebay" /></template>
