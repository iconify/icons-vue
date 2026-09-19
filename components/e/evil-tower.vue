<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg221mb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sg221mb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-tower" /></template>
