<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv842m9yr.css';
import '../../css/f/fl7bzqbcv.css';
import '../../css/n/nhkqt2bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yv842m9yr"/><path class="fl7bzqbcv"/><path class="nhkqt2bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:library-20-bold" /></template>
