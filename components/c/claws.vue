<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsf5x-bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qsf5x-bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:claws" /></template>
