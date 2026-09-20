<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6glyvb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6glyvb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:home-simple-line" /></template>
