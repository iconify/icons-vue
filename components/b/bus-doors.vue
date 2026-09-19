<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj-sz3bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dj-sz3bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bus-doors" /></template>
