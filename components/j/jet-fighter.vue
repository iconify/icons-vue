<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l61alz7vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l61alz7vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jet-fighter" /></template>
