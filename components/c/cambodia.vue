<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsa27y-9e.css';
import '../../css/v/vvve78bba.css';
import '../../css/u/uzl62cwjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="qsa27y-9e"/><path class="vvve78bba"/><path class="uzl62cwjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:cambodia" /></template>
