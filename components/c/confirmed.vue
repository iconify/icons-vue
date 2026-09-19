<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj0_4iwbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj0_4iwbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:confirmed" /></template>
