<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npdk0lbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npdk0lbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:azul-flake" /></template>
