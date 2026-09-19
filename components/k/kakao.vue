<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqibk0bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="sqibk0bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:kakao" /></template>
