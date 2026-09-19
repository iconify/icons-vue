<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmyfv_bvg.css';
import '../../css/o/o9ffdfb9u.css';
import '../../css/w/wgqpd53tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="vmyfv_bvg"/><path class="o9ffdfb9u"/><path class="wgqpd53tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:fr-4x3" /></template>
