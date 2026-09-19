<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqsjmzzkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="lqsjmzzkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:gulp" /></template>
