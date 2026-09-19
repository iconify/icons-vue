<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc96r_bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc96r_bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:discussion" /></template>
