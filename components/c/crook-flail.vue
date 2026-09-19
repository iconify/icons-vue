<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0dxcsb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0dxcsb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crook-flail" /></template>
