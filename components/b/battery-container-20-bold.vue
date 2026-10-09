<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6dgzbb5r.css';
import '../../css/j/jd4w5xjrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i6dgzbb5r"/><path class="jd4w5xjrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-container-20-bold" /></template>
