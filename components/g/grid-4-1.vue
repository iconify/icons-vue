<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmjv_lbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmjv_lbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:grid-4-1" /></template>
