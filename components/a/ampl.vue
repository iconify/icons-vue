<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw659x9es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rw659x9es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ampl" /></template>
