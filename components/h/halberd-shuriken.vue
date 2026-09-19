<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynfd2zbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ynfd2zbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:halberd-shuriken" /></template>
