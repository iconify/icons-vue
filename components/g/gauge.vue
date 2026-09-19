<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3o5_cbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d3o5_cbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:gauge" /></template>
