<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6lmwybxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6lmwybxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gutenberg" /></template>
