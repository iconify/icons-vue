<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm5wywbws.css';
import '../../css/v/v6mgv7b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wm5wywbws"/><path class="v6mgv7b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:docked-top" /></template>
