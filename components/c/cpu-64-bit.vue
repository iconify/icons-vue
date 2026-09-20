<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgcn9lbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgcn9lbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cpu-64-bit" /></template>
