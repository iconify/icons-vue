<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jowh1fb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jowh1fb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clapperboard" /></template>
