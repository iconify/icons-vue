<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkyg13wqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkyg13wqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:help" /></template>
