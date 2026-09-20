<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1vzvobrg.css';
import '../../css/s/sco2ncz2j.css';
import '../../css/t/tgu2pcaid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1vzvobrg"/><path class="sco2ncz2j"/><path clip-rule="evenodd" class="tgu2pcaid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:card-game-card-spade" /></template>
