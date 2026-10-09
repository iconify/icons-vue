<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njicu-b5r.css';
import '../../css/i/i2ndmodxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="njicu-b5r"/><path class="i2ndmodxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frame-20" /></template>
