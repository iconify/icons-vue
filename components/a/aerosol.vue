<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plxs-nt5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plxs-nt5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:aerosol" /></template>
