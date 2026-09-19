<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az254abpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="az254abpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broken-skull" /></template>
