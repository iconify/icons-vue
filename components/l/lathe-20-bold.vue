<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7d4ky4we.css';
import '../../css/p/polb77bwu.css';
import '../../css/s/sorlblovj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c7d4ky4we"/><path class="polb77bwu"/><path class="sorlblovj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lathe-20-bold" /></template>
