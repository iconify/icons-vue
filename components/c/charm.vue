<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0fxzdw3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0fxzdw3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:charm" /></template>
