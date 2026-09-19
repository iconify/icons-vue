<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs7-nlzox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs7-nlzox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-minion" /></template>
