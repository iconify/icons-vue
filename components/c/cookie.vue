<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8pbwebty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f8pbwebty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cookie" /></template>
