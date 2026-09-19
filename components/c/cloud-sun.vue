<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5hyxqbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5hyxqbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:cloud-sun" /></template>
