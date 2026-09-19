<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9u-62fmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9u-62fmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:home" /></template>
