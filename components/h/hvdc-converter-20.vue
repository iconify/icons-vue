<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti48nsbex.css';
import '../../css/a/ar3qzv4of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti48nsbex"/><path class="ar3qzv4of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hvdc-converter-20" /></template>
