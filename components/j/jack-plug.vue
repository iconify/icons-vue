<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvx9auxoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvx9auxoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jack-plug" /></template>
