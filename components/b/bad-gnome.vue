<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n54h2kbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n54h2kbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bad-gnome" /></template>
