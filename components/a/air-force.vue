<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5jtt9gnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5jtt9gnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:air-force" /></template>
