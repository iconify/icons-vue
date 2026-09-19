<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-i1jgb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t-i1jgb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:angellist" /></template>
