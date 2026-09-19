<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mns0wob5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mns0wob5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bolter-gun" /></template>
