<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l28ij0y1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l28ij0y1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-lock" /></template>
