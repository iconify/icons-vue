<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg49w7bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jg49w7bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:level-two-advanced" /></template>
