<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyts_6b4x.css';
import '../../css/f/fu4k6tlst.css';
import '../../css/x/xpbh4hvld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kyts_6b4x"/><path class="fu4k6tlst"/><path class="xpbh4hvld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blueprint-48-bold" /></template>
