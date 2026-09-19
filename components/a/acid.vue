<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct5am5bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ct5am5bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:acid" /></template>
