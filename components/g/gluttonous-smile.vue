<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvgu6skht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvgu6skht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gluttonous-smile" /></template>
