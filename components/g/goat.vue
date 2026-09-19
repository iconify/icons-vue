<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spaeb_25g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spaeb_25g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:goat" /></template>
