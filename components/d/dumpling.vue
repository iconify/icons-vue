<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs1j0v5_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vs1j0v5_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dumpling" /></template>
