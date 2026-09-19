<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu5qq_bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iu5qq_bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-hand" /></template>
