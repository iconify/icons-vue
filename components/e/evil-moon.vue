<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1iia1cmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l1iia1cmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-moon" /></template>
