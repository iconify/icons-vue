<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-27zd6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iq-27zd6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bombing-run" /></template>
