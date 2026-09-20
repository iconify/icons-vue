<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/a/ab6j9p.css';
import '../../css/j/jzrnzz.css';
import '../../css/x/xr4k_q.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ab6j9p"/><path class="a0m25c jzrnzz"/><path class="a0m25c xr4k_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-triple-down" /></template>
