<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8cq105ge.css';
import '../../css/r/r7j0j19px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j8cq105ge"/><path class="r7j0j19px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidity-20" /></template>
