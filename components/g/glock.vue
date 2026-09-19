<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmbr0-b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmbr0-b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glock" /></template>
