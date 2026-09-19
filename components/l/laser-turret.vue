<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1_8-ry_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1_8-ry_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:laser-turret" /></template>
