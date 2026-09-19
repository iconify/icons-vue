<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvfqs5zsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvfqs5zsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:graveyard" /></template>
