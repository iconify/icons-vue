<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo6c3-5uk.css';
import '../../css/f/f-7sbkbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fo6c3-5uk"/><path class="f-7sbkbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:enumeration-usage" /></template>
