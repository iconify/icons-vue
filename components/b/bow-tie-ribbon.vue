<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj7o5x-om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj7o5x-om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bow-tie-ribbon" /></template>
