<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfb5v-moa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dfb5v-moa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drama-masks" /></template>
