<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0y37gbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0y37gbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fort" /></template>
