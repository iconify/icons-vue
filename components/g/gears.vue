<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp5l44u1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rp5l44u1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gears" /></template>
