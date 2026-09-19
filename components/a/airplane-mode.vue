<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5ecs8zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq5ecs8zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:airplane-mode" /></template>
