<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y84s00bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y84s00bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:currency-ruble" /></template>
