<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugt25bbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugt25bbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:ice-cream" /></template>
