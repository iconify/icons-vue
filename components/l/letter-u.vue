<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnv1knkjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnv1knkjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-u" /></template>
