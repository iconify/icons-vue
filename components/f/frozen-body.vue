<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3-ph0b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3-ph0b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frozen-body" /></template>
