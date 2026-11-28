<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6s8su6gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6s8su6gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:badge-percent-check" /></template>
