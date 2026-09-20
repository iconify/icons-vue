<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi1t57hvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi1t57hvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-justify" /></template>
