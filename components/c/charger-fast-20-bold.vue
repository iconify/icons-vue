<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r__2x3s5d.css';
import '../../css/c/cjbp44b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r__2x3s5d"/><path class="cjbp44b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fast-20-bold" /></template>
