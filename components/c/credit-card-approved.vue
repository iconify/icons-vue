<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcks5cuuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mcks5cuuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:credit-card-approved" /></template>
