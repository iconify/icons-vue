<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owm_lybuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="owm_lybuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-028" /></template>
