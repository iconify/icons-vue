<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmx3obbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmx3obbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:escalator" /></template>
