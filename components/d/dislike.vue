<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb-tf8bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="tb-tf8bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:dislike" /></template>
