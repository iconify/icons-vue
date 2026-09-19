<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f61j_no4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f61j_no4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:alien-fire" /></template>
