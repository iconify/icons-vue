<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w458axn3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w458axn3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:condor-emblem" /></template>
