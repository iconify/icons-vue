<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fce-beu8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fce-beu8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:at" /></template>
