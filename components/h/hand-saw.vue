<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mem9ylb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mem9ylb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hand-saw" /></template>
