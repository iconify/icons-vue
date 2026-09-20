<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6tmrrbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f6tmrrbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:disc-golf-basket" /></template>
