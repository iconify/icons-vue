<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx371419d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bx371419d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-9-clubs" /></template>
