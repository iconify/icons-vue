<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urb3y9b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="urb3y9b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dough-roller" /></template>
