<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj243w90a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aj243w90a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brain-freeze" /></template>
