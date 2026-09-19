<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6wisacjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6wisacjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:locked-heart" /></template>
