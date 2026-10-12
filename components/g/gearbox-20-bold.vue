<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncnjsrrtg.css';
import '../../css/m/mo1ard8kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ncnjsrrtg"/><path class="mo1ard8kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gearbox-20-bold" /></template>
