<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obbjn7b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obbjn7b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:film-strip" /></template>
