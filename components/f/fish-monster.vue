<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l36ys2b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l36ys2b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fish-monster" /></template>
