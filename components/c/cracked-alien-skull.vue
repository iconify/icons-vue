<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvd7w_b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvd7w_b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cracked-alien-skull" /></template>
