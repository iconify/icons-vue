<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu01-jbtn.css';
import '../../css/r/rspsi8b7x.css';
import '../../css/g/ganklmxwt.css';
import '../../css/e/etikf8b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vu01-jbtn"/><path class="rspsi8b7x"/><path class="ganklmxwt"/><path class="etikf8b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-bike-20" /></template>
