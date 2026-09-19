<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob0wpqbjp.css';
import '../../css/h/h_4w4ru8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ob0wpqbjp"/><path class="h_4w4ru8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:license-global" /></template>
