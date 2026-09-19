<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_eewhbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_eewhbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bandaged" /></template>
