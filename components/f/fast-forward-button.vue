<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm1kpib8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jm1kpib8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fast-forward-button" /></template>
