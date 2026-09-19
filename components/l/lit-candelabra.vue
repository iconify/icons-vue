<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er_pfrsbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="er_pfrsbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lit-candelabra" /></template>
