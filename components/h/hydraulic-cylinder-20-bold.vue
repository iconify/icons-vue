<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6-6-wgev.css';
import '../../css/t/tyoqu7bub.css';
import '../../css/l/l91t7i1ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y6-6-wgev"/><path class="tyoqu7bub"/><path class="l91t7i1ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydraulic-cylinder-20-bold" /></template>
