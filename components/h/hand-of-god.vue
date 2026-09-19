<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe3yhcbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe3yhcbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hand-of-god" /></template>
