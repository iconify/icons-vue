<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yla7zvbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yla7zvbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abacus" /></template>
