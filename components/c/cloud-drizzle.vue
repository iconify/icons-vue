<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl74d_b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl74d_b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:cloud-drizzle" /></template>
