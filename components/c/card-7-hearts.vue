<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4mf6cdoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4mf6cdoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-7-hearts" /></template>
