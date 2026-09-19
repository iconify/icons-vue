<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suu9lebdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="suu9lebdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:daisy" /></template>
