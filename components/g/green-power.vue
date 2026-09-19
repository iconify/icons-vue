<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ak47bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6ak47bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:green-power" /></template>
