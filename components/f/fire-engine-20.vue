<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9jo7bca.css';
import '../../css/r/r5ivvvbes.css';
import '../../css/r/r7w_ozowo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="um9jo7bca"/><path class="r5ivvvbes"/><path class="r7w_ozowo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-engine-20" /></template>
