<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrdg1_n9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrdg1_n9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:linkedin" /></template>
