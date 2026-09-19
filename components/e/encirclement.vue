<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqijej_rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqijej_rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:encirclement" /></template>
