<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oks577bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oks577bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fast-arrow" /></template>
