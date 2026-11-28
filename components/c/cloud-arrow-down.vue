<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs13libeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs13libeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-arrow-down" /></template>
