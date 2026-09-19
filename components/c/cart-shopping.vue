<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt6qkccya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="nt6qkccya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cart-shopping" /></template>
