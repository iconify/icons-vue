<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5z_ev-up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5z_ev-up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dog-house" /></template>
