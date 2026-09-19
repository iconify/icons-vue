<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj9nv3q3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mj9nv3q3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glider" /></template>
