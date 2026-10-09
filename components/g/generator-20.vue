<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs6pf8bqr.css';
import '../../css/r/rtbfcmafp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cs6pf8bqr"/><path class="rtbfcmafp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:generator-20" /></template>
