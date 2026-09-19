<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmx42-grk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmx42-grk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heaven-gate" /></template>
