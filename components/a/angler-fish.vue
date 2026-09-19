<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii5c8ebjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii5c8ebjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:angler-fish" /></template>
