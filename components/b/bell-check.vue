<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5pexac2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5pexac2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bell-check" /></template>
