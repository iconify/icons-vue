<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crozqj1qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="crozqj1qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:implosion" /></template>
