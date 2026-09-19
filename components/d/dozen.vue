<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y99voxbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y99voxbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dozen" /></template>
