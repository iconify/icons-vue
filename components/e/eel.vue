<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky3lmks1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ky3lmks1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eel" /></template>
