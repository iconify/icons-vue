<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pntcq57kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pntcq57kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-arrow-up" /></template>
