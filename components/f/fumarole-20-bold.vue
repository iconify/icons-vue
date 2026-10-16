<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9w3oq-xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r9w3oq-xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fumarole-20-bold" /></template>
