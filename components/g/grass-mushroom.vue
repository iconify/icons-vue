<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgyfw-bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgyfw-bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grass-mushroom" /></template>
