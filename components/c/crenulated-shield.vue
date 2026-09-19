<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uayu3q91h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uayu3q91h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crenulated-shield" /></template>
