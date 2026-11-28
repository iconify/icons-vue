<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thfl-dbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thfl-dbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:brain-check" /></template>
