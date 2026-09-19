<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uywq6lb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uywq6lb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burning-skull" /></template>
