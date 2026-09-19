<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk2_g9b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qk2_g9b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-circle-arrow-right" /></template>
