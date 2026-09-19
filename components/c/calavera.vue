<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blmhbm1pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blmhbm1pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:calavera" /></template>
