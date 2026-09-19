<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na_o-44vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="na_o-44vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flower-emblem" /></template>
