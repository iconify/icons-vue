<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq14ewv-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zq14ewv-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:lock" /></template>
