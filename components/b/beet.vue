<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ezc3bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7ezc3bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beet" /></template>
