<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wws2w5bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wws2w5bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chart-bar" /></template>
