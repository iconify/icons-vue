<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6kqlu_fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6kqlu_fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:3d-meeple" /></template>
