<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsi11wb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsi11wb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:key-lock" /></template>
