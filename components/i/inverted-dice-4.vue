<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h89pxybiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h89pxybiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inverted-dice-4" /></template>
