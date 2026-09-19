<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn21aqyxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pn21aqyxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-delicious" /></template>
