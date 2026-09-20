<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iez2hnbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iez2hnbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:beverages-14" /></template>
