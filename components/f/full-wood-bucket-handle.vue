<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_kis0uyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_kis0uyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:full-wood-bucket-handle" /></template>
