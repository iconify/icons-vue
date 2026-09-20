<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf06j_bww.css';
import '../../css/r/rsco9dbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bf06j_bww"/><path class="rsco9dbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-skull-2" /></template>
