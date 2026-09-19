<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq2ekwa6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq2ekwa6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gamepad" /></template>
