<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro0w3__dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ro0w3__dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hooded-assassin" /></template>
