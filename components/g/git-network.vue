<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_5ttnbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_5ttnbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-network" /></template>
