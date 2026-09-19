<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhi3crign.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhi3crign"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:donkey" /></template>
