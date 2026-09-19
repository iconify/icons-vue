<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pszgp0b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pszgp0b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bottled-shadow" /></template>
