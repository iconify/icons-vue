<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whbq-6bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="whbq-6bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:die-face-with-two-pips" /></template>
