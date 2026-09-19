<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx1ugx-4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hx1ugx-4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hearing-disabled" /></template>
