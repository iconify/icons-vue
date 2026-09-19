<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9g-hpb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t9g-hpb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blanket" /></template>
