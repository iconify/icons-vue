<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foac8gxdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="foac8gxdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:fahrenheit" /></template>
