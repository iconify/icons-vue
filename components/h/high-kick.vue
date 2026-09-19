<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1wyn0pqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1wyn0pqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:high-kick" /></template>
