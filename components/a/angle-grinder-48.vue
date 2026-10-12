<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw15abcyx.css';
import '../../css/d/d2sisx8fh.css';
import '../../css/j/jge7z1bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pw15abcyx"/><path class="d2sisx8fh"/><path class="jge7z1bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:angle-grinder-48" /></template>
