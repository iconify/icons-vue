<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iohkho2qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iohkho2qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:discount-1" /></template>
