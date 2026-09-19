<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym1u7k0hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ym1u7k0hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bread" /></template>
