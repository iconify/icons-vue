<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szp3pvb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szp3pvb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-punch" /></template>
