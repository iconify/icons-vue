<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnx5jt5yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1440,"height":1440};
const content = `<path class="rnx5jt5yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:designali" /></template>
