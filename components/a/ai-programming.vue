<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/ffr29_hhx.css';
import '../../css/d/dg7qrmb6g.css';
import '../../css/u/umbt3k8ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ffr29_hhx"/><path class="dg7qrmb6g"/><path class="umbt3k8ug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-programming" /></template>
