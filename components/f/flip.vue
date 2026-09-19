<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9o1olbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e9o1olbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:flip" /></template>
