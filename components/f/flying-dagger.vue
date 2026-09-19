<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5-7_mbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5-7_mbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flying-dagger" /></template>
