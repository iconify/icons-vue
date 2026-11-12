<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvnewqbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pvnewqbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excalidraw" /></template>
