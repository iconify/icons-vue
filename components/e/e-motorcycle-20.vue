<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8hrjq-xz.css';
import '../../css/u/uaje_hxks.css';
import '../../css/f/fybuv2jvo.css';
import '../../css/p/ppols2b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i8hrjq-xz"/><path class="uaje_hxks"/><path class="fybuv2jvo"/><path class="ppols2b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-motorcycle-20" /></template>
