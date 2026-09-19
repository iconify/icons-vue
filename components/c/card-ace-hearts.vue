<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us13qnh4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="us13qnh4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-ace-hearts" /></template>
