<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dincmk2_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dincmk2_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bolt-cutter" /></template>
