<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd3xn7bgt.css';
import '../../css/y/yj19_b3-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xd3xn7bgt"/><path class="yj19_b3-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-battery-20-bold" /></template>
