<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkveo32rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hkveo32rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barracks-tent" /></template>
