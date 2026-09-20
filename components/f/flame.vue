<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrdps6byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rrdps6byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:flame" /></template>
