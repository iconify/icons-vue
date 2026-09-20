<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu81sg07k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu81sg07k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:centimeter" /></template>
