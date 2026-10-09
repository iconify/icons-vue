<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkpulpb9y.css';
import '../../css/p/p1om3-m6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="p1om3-m6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:app-window-20-bold" /></template>
