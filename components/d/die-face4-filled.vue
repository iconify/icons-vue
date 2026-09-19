<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emu97kndw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="emu97kndw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face4-filled" /></template>
