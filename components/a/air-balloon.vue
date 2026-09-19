<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmlu3limk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmlu3limk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:air-balloon" /></template>
