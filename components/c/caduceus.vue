<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkncd8bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mkncd8bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:caduceus" /></template>
