<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd637ybny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd637ybny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:logic-gate-or" /></template>
