<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifsx8zb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ifsx8zb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bird-claw" /></template>
