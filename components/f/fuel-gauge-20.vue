<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d03rjttsh.css';
import '../../css/x/x4s1haczx.css';
import '../../css/f/fi3lb_64h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d03rjttsh"/><path class="x4s1haczx"/><path class="fi3lb_64h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-gauge-20" /></template>
