<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu9ipebir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tu9ipebir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ivory-tusks" /></template>
