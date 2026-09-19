<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnj8a2e8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tnj8a2e8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fog-light" /></template>
