<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y45nhlkin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y45nhlkin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:catapult" /></template>
