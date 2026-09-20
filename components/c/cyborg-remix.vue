<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgvl3po6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jgvl3po6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cyborg-remix" /></template>
