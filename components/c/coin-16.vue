<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1_ko4blm.css';
import '../../css/x/xqqc18b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j1_ko4blm"/><path clip-rule="evenodd" class="xqqc18b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:coin-16" /></template>
