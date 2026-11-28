<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll162-brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll162-brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:basket-minus" /></template>
