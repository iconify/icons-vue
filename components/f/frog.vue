<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgo93hedx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgo93hedx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:frog" /></template>
