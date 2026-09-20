<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrx4z5b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrx4z5b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:arrowleftalt" /></template>
