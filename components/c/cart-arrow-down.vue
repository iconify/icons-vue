<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs0dntbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs0dntbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cart-arrow-down" /></template>
