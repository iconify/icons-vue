<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgaal2y-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgaal2y-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:doner-kebab" /></template>
