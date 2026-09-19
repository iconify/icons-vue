<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1xiq3osc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="y1xiq3osc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cart-flatbed-suitcase" /></template>
