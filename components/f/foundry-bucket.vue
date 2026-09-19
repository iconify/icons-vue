<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao4wlibpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ao4wlibpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:foundry-bucket" /></template>
