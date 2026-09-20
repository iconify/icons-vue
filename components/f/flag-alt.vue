<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh8oi_0yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nh8oi_0yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:flag-alt" /></template>
