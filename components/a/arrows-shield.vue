<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok8n22bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ok8n22bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrows-shield" /></template>
