<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wipq2ibhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wipq2ibhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bulldozer" /></template>
