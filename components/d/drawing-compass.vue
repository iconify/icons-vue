<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lavm11ltb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lavm11ltb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:drawing-compass" /></template>
