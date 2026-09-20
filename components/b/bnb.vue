<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj3fg93gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj3fg93gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bnb" /></template>
