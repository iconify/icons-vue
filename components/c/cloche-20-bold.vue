<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bljjpbbly.css';
import '../../css/w/whrztoabz.css';
import '../../css/k/kai1ahz2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bljjpbbly"/><path class="whrztoabz"/><path class="kai1ahz2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloche-20-bold" /></template>
