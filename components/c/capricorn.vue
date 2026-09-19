<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-2-3xob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb-2-3xob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:capricorn" /></template>
