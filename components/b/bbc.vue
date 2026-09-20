<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkvwa7bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":285};
const content = `<path class="kkvwa7bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bbc" /></template>
