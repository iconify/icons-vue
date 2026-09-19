<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brr5v30ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brr5v30ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:candle-skull" /></template>
