<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvy1pybls.css';
import '../../css/g/g63v8lcab.css';
import '../../css/i/ieb8qdn3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lvy1pybls"/><path class="g63v8lcab"/><path class="ieb8qdn3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:log-in-20-bold" /></template>
