<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_t7240v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_t7240v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:circle-7" /></template>
