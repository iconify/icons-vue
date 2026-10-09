<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0v1yf7ii.css';
import '../../css/u/u_sp4-r9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x0v1yf7ii"/><path class="u_sp4-r9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-check-20" /></template>
