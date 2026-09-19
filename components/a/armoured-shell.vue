<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9_o2-3ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9_o2-3ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armoured-shell" /></template>
