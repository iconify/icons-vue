<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz76bebrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz76bebrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-lock" /></template>
