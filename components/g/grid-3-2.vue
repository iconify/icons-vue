<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5h_42yze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5h_42yze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:grid-3-2" /></template>
