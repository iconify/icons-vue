<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq13s2klb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iq13s2klb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-bolt" /></template>
