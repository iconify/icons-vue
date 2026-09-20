<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmrqh5bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mmrqh5bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:inbox-remix" /></template>
