<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0r16-fkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0r16-fkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:knee-cap" /></template>
