<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufaounboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufaounboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cart-arrow-down" /></template>
