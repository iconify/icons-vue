<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucjk_d2la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucjk_d2la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:glass" /></template>
