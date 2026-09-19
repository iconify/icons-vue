<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4jkx3bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4jkx3bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:cloud-off" /></template>
