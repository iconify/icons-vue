<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moa--4apo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="moa--4apo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boombox" /></template>
