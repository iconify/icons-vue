<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p28nk78it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p28nk78it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beams-aura" /></template>
