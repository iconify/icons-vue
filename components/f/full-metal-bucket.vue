<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpd_n5uta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kpd_n5uta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:full-metal-bucket" /></template>
