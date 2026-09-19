<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3khll-_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3khll-_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:goo-spurt" /></template>
