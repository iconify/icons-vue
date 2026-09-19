<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymua60nhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymua60nhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cracked-helm" /></template>
