<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpsmi2bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpsmi2bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:conqueror" /></template>
