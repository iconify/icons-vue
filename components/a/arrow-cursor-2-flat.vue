<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp2cgibwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sp2cgibwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:arrow-cursor-2-flat" /></template>
