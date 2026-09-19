<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzwbhrw3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzwbhrw3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cross-mark" /></template>
