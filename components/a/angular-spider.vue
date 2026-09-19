<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m21ieoben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m21ieoben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:angular-spider" /></template>
