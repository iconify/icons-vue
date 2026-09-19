<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v33qmxlfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v33qmxlfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-102" /></template>
