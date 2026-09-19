<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh5l98-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gnh5l98-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-6-hearts" /></template>
