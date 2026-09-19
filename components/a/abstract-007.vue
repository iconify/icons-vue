<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5k7lbbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5k7lbbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-007" /></template>
