<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p928398kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p928398kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:die-face-with-six-pips" /></template>
