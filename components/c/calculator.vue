<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4-_1ab-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="l4-_1ab-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:calculator" /></template>
