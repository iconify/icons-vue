<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsbipqluu.css';
import '../../css/m/m723m1bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lsbipqluu"/><path clip-rule="evenodd" class="m723m1bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:check-in-circle-empty" /></template>
