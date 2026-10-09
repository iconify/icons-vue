<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry_fo9lxv.css';
import '../../css/x/x7suexyet.css';
import '../../css/e/eeqn6pbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ry_fo9lxv"/><path class="x7suexyet"/><path class="eeqn6pbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-ferry-20" /></template>
