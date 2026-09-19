<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcsx5kbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pcsx5kbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling-blob" /></template>
