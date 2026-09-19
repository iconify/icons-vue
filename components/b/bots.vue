<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1hdpcc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="n1hdpcc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:bots" /></template>
