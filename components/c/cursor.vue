<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziyq9ys9s.css';
import '../../css/q/qgoa3-pny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(.92099 0 0 .92169 -.41 .382)" class="ziyq9ys9s"/><path class="qgoa3-pny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cursor" /></template>
