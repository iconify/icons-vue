<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv89jg_sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uv89jg_sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-footprint-20" /></template>
