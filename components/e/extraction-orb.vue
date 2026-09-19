<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3m_y-zfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3m_y-zfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:extraction-orb" /></template>
