<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htg2ctj4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="htg2ctj4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:kakao-square" /></template>
