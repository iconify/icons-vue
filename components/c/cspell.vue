<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sahvilbsv.css';
import '../../css/q/qwfd1bbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sahvilbsv"/><path class="qwfd1bbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cspell" /></template>
