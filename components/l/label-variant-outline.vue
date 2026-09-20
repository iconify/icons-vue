<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxfri69yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxfri69yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:label-variant-outline" /></template>
