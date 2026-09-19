<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1pi5rbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m1pi5rbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-graph-down-right" /></template>
