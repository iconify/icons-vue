<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whz263bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="whz263bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:enj" /></template>
