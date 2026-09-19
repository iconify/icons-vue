<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odnofr3te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odnofr3te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magnet-blast" /></template>
