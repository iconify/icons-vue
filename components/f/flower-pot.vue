<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/issceubax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="issceubax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flower-pot" /></template>
