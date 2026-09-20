<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1nd-duxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":24};
const content = `<path class="z1nd-duxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:back-outlined" /></template>
