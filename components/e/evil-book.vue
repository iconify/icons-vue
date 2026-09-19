<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcsvi2buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcsvi2buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-book" /></template>
