<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh0tp9bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qh0tp9bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fleur-de-lys" /></template>
