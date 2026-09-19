<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wagyafbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wagyafbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bowen-knot" /></template>
