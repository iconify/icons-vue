<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubrg13b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ubrg13b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:egyptian-temple" /></template>
