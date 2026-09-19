<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-idqibds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-idqibds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:0xbtc" /></template>
