<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q97qiwbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="q97qiwbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:apple" /></template>
