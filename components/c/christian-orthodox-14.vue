<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou116yntr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ou116yntr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:christian-orthodox-14" /></template>
