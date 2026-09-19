<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6xmx6owm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6xmx6owm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:box-list" /></template>
