<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1o_6mbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1o_6mbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:back-pain" /></template>
