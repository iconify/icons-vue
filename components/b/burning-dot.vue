<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9ki65buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9ki65buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burning-dot" /></template>
