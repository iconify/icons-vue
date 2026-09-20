<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9d05fmzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y9d05fmzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:circle-flat" /></template>
