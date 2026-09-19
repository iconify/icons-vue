<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjsqj1b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fjsqj1b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:game-die-small" /></template>
