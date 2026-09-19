<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pplcewb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pplcewb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossbow" /></template>
