<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv_r1s6dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv_r1s6dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:car-door" /></template>
