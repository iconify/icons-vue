<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wel6qxzrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wel6qxzrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:drone-x" /></template>
