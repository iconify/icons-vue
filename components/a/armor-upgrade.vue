<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-dig_o-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-dig_o-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armor-upgrade" /></template>
