<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo7f0lbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uo7f0lbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:cog" /></template>
