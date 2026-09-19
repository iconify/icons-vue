<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcc15usle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcc15usle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:agave" /></template>
