<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt55pmb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":459,"height":512};
const content = `<path class="pt55pmb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:c-script" /></template>
