<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_nf9ib3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_nf9ib3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:align-left" /></template>
