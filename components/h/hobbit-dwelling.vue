<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdgzzcb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pdgzzcb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hobbit-dwelling" /></template>
