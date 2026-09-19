<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jctdg3jzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jctdg3jzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:croissants-pupil" /></template>
