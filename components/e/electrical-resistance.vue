<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyx608bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyx608bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:electrical-resistance" /></template>
