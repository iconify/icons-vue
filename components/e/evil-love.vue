<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc1bpgixu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc1bpgixu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-love" /></template>
