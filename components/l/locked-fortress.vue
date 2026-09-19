<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4znhhbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c4znhhbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:locked-fortress" /></template>
