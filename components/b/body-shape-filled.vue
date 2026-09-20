<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo0he1bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo0he1bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:body-shape-filled" /></template>
