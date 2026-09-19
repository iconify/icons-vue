<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm-gy2bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm-gy2bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eyedropper" /></template>
