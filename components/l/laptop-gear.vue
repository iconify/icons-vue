<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0zr3cc4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0zr3cc4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:laptop-gear" /></template>
