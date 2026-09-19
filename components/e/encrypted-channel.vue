<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufi2aab_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ufi2aab_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:encrypted-channel" /></template>
