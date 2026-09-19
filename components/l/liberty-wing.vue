<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y98jkdbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y98jkdbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:liberty-wing" /></template>
