<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv9x1msdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iv9x1msdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:desert" /></template>
