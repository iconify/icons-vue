<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk6drtbrj.css';
import '../../css/t/t2iyet0dj.css';
import '../../css/g/ga8o6nb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xk6drtbrj"/><path class="t2iyet0dj"/><path class="ga8o6nb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-right-20-bold" /></template>
