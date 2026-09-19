<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsn1rm4hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsn1rm4hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:deathcab" /></template>
