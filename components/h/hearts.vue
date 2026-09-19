<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf6-8eb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf6-8eb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hearts" /></template>
