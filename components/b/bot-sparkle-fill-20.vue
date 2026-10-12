<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdcxh6dac.css';
import '../../css/r/rsf6pbc-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wdcxh6dac"/><path class="rsf6pbc-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bot-sparkle-fill-20" /></template>
