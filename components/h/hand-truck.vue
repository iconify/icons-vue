<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mju1_f0cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mju1_f0cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hand-truck" /></template>
