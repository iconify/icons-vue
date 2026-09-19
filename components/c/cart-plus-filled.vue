<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmot0ebfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmot0ebfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-plus-filled" /></template>
