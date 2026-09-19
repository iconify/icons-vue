<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt3-4rb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt3-4rb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:grid-4-2" /></template>
