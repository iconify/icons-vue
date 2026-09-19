<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdish1bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdish1bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:beaker-1" /></template>
