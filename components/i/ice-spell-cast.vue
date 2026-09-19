<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw06pbbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mw06pbbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-spell-cast" /></template>
