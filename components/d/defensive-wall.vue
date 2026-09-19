<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwf9ewb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwf9ewb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:defensive-wall" /></template>
