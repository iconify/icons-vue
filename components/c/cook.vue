<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouer3jrlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouer3jrlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cook" /></template>
