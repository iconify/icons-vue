<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbu_57tmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbu_57tmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hell-crosses" /></template>
