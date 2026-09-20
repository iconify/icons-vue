<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtwew_qxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rtwew_qxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:location" /></template>
