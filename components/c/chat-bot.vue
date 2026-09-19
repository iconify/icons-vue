<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glp2bkbii.css';
import '../../css/m/mynrssntn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="glp2bkbii"/><path class="mynrssntn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chat-bot" /></template>
