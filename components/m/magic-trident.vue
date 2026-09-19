<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx3is3rfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tx3is3rfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-trident" /></template>
