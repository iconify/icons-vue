<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cca_t3yjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cca_t3yjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:antarctica" /></template>
