<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2v73ib3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2v73ib3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hexes" /></template>
