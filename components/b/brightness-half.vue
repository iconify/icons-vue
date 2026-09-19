<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/car149bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="car149bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:brightness-half" /></template>
