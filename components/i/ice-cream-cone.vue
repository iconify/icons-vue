<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghpm_5bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghpm_5bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-cream-cone" /></template>
