<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgzbipb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fgzbipb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blaster" /></template>
