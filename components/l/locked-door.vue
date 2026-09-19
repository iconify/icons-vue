<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n95_fnbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n95_fnbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:locked-door" /></template>
