<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-x0dsblc.css';
import '../../css/y/ydysvhh_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-x0dsblc"/><path class="ydysvhh_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:forward-30" /></template>
